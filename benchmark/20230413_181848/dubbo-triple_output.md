# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.541 ops/ms
# Warmup Iteration   2: 3.827 ops/ms
# Warmup Iteration   3: 7.475 ops/ms
Iteration   1: 7.373 ops/ms
Iteration   2: 7.662 ops/ms
Iteration   3: 7.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.649 ±(99.9%) 4.899 ops/ms [Average]
  (min, avg, max) = (7.373, 7.649, 7.910), stdev = 0.269
  CI (99.9%): [2.750, 12.547] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.166 ops/ms
# Warmup Iteration   2: 6.917 ops/ms
# Warmup Iteration   3: 7.941 ops/ms
Iteration   1: 8.564 ops/ms
Iteration   2: 8.618 ops/ms
Iteration   3: 8.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.611 ±(99.9%) 0.818 ops/ms [Average]
  (min, avg, max) = (8.564, 8.611, 8.652), stdev = 0.045
  CI (99.9%): [7.794, 9.429] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.986 ops/ms
# Warmup Iteration   2: 6.662 ops/ms
# Warmup Iteration   3: 7.481 ops/ms
Iteration   1: 8.006 ops/ms
Iteration   2: 8.051 ops/ms
Iteration   3: 8.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.068 ±(99.9%) 1.320 ops/ms [Average]
  (min, avg, max) = (8.006, 8.068, 8.148), stdev = 0.072
  CI (99.9%): [6.748, 9.388] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.891 ops/ms
# Warmup Iteration   2: 5.914 ops/ms
# Warmup Iteration   3: 6.519 ops/ms
Iteration   1: 6.851 ops/ms
Iteration   2: 6.657 ops/ms
Iteration   3: 6.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.770 ±(99.9%) 1.837 ops/ms [Average]
  (min, avg, max) = (6.657, 6.770, 6.851), stdev = 0.101
  CI (99.9%): [4.933, 8.607] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 13.356 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.777 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.075 ±(99.9%) 0.010 ms/op
Iteration   1: 3.943 ±(99.9%) 0.007 ms/op
Iteration   2: 3.844 ±(99.9%) 0.014 ms/op
Iteration   3: 3.876 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.888 ±(99.9%) 0.915 ms/op [Average]
  (min, avg, max) = (3.844, 3.888, 3.943), stdev = 0.050
  CI (99.9%): [2.973, 4.803] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.536 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.846 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.004 ms/op
Iteration   1: 3.826 ±(99.9%) 0.004 ms/op
Iteration   2: 3.845 ±(99.9%) 0.005 ms/op
Iteration   3: 3.764 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.812 ±(99.9%) 0.770 ms/op [Average]
  (min, avg, max) = (3.764, 3.812, 3.845), stdev = 0.042
  CI (99.9%): [3.041, 4.582] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 13.374 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.640 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.162 ±(99.9%) 0.010 ms/op
Iteration   1: 4.179 ±(99.9%) 0.005 ms/op
Iteration   2: 3.993 ±(99.9%) 0.007 ms/op
Iteration   3: 3.943 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.038 ±(99.9%) 2.276 ms/op [Average]
  (min, avg, max) = (3.943, 4.038, 4.179), stdev = 0.125
  CI (99.9%): [1.763, 6.314] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 13.025 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 6.442 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.772 ±(99.9%) 0.014 ms/op
Iteration   1: 4.551 ±(99.9%) 0.011 ms/op
Iteration   2: 4.575 ±(99.9%) 0.018 ms/op
Iteration   3: 4.634 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.587 ±(99.9%) 0.782 ms/op [Average]
  (min, avg, max) = (4.551, 4.587, 4.634), stdev = 0.043
  CI (99.9%): [3.805, 5.369] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.863 ±(99.9%) 0.186 ms/op
# Warmup Iteration   2: 5.273 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.365 ±(99.9%) 0.016 ms/op
Iteration   1: 4.046 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.229 ms/op
                 createUser·p0.50:   3.912 ms/op
                 createUser·p0.90:   4.596 ms/op
                 createUser·p0.95:   5.038 ms/op
                 createUser·p0.99:   7.709 ms/op
                 createUser·p0.999:  24.632 ms/op
                 createUser·p0.9999: 31.982 ms/op
                 createUser·p1.00:   32.735 ms/op

Iteration   2: 3.928 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.896 ms/op
                 createUser·p0.50:   3.834 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   6.695 ms/op
                 createUser·p0.999:  15.245 ms/op
                 createUser·p0.9999: 32.599 ms/op
                 createUser·p1.00:   33.391 ms/op

Iteration   3: 3.922 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   3.777 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  28.690 ms/op
                 createUser·p0.9999: 32.464 ms/op
                 createUser·p1.00:   33.128 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 242102
  mean =      3.965 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 385 
    [ 2.500,  5.000) = 232044 
    [ 5.000,  7.500) = 7973 
    [ 7.500, 10.000) = 967 
    [10.000, 12.500) = 336 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 102 
    [30.000, 32.500) = 103 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     24.173 ms/op
     p(99.9900) =     32.408 ms/op
     p(99.9990) =     33.128 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.912 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.468 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.870 ±(99.9%) 0.011 ms/op
Iteration   1: 3.866 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.784 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.268 ms/op
                 existUser·p0.95:   5.325 ms/op
                 existUser·p0.99:   7.002 ms/op
                 existUser·p0.999:  16.253 ms/op
                 existUser·p0.9999: 25.836 ms/op
                 existUser·p1.00:   26.575 ms/op

Iteration   2: 3.777 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.554 ms/op
                 existUser·p0.50:   3.633 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   6.439 ms/op
                 existUser·p0.999:  23.606 ms/op
                 existUser·p0.9999: 26.822 ms/op
                 existUser·p1.00:   27.951 ms/op

Iteration   3: 3.803 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.415 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.162 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   7.043 ms/op
                 existUser·p0.999:  15.100 ms/op
                 existUser·p0.9999: 32.722 ms/op
                 existUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 251438
  mean =      3.815 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 261 
    [ 2.500,  5.000) = 240999 
    [ 5.000,  7.500) = 8485 
    [ 7.500, 10.000) = 1023 
    [10.000, 12.500) = 355 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.415 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     16.279 ms/op
     p(99.9900) =     31.392 ms/op
     p(99.9990) =     33.586 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.380 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.971 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.326 ±(99.9%) 0.017 ms/op
Iteration   1: 4.027 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.858 ms/op
                 getUser·p0.50:   3.899 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   7.938 ms/op
                 getUser·p0.999:  23.953 ms/op
                 getUser·p0.9999: 29.839 ms/op
                 getUser·p1.00:   30.409 ms/op

Iteration   2: 3.872 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.350 ms/op
                 getUser·p0.50:   3.736 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   7.201 ms/op
                 getUser·p0.999:  14.730 ms/op
                 getUser·p0.9999: 27.427 ms/op
                 getUser·p1.00:   28.312 ms/op

Iteration   3: 4.003 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.958 ms/op
                 getUser·p0.50:   3.912 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   4.923 ms/op
                 getUser·p0.99:   6.899 ms/op
                 getUser·p0.999:  13.770 ms/op
                 getUser·p0.9999: 29.393 ms/op
                 getUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 241924
  mean =      3.966 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 232838 
    [ 5.000,  7.500) = 6743 
    [ 7.500, 10.000) = 1471 
    [10.000, 12.500) = 382 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 102 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     14.962 ms/op
     p(99.9900) =     29.092 ms/op
     p(99.9990) =     30.381 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.166 ±(99.9%) 0.224 ms/op
# Warmup Iteration   2: 5.640 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.772 ±(99.9%) 0.017 ms/op
Iteration   1: 4.749 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.917 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   7.266 ms/op
                 listUser·p0.99:   8.880 ms/op
                 listUser·p0.999:  25.035 ms/op
                 listUser·p0.9999: 28.058 ms/op
                 listUser·p1.00:   28.738 ms/op

Iteration   2: 4.628 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   8.315 ms/op
                 listUser·p0.999:  18.973 ms/op
                 listUser·p0.9999: 41.753 ms/op
                 listUser·p1.00:   42.861 ms/op

Iteration   3: 4.701 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.548 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   9.423 ms/op
                 listUser·p0.999:  16.843 ms/op
                 listUser·p0.9999: 22.610 ms/op
                 listUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204433
  mean =      4.692 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 171689 
    [ 5.000, 10.000) = 31524 
    [10.000, 15.000) = 751 
    [15.000, 20.000) = 245 
    [20.000, 25.000) = 123 
    [25.000, 30.000) = 69 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 14 
    [40.000, 45.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.917 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      8.831 ms/op
     p(99.9000) =     20.677 ms/op
     p(99.9900) =     37.684 ms/op
     p(99.9990) =     42.727 ms/op
     p(99.9999) =     42.861 ms/op
    p(100.0000) =     42.861 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.649 ± 4.899  ops/ms
ClientPb.existUser                       thrpt       3   8.611 ± 0.818  ops/ms
ClientPb.getUser                         thrpt       3   8.068 ± 1.320  ops/ms
ClientPb.listUser                        thrpt       3   6.770 ± 1.837  ops/ms
ClientPb.createUser                       avgt       3   3.888 ± 0.915   ms/op
ClientPb.existUser                        avgt       3   3.812 ± 0.770   ms/op
ClientPb.getUser                          avgt       3   4.038 ± 2.276   ms/op
ClientPb.listUser                         avgt       3   4.587 ± 0.782   ms/op
ClientPb.createUser                     sample  242102   3.965 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.075           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.514           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.866           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.717           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.173           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.408           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.391           ms/op
ClientPb.existUser                      sample  251438   3.815 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.415           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.186           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.637           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.783           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.279           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.392           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.144           ms/op
ClientPb.getUser                        sample  241924   3.966 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.350           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.743           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.324           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.962           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.092           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.409           ms/op
ClientPb.listUser                       sample  204433   4.692 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.917           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.276           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.906           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.831           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.677           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.684           ms/op
ClientPb.listUser:listUser·p1.00        sample          42.861           ms/op
