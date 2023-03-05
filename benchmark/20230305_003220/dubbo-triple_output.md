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
# Warmup Iteration   1: 1.942 ops/ms
# Warmup Iteration   2: 4.300 ops/ms
# Warmup Iteration   3: 7.280 ops/ms
Iteration   1: 8.058 ops/ms
Iteration   2: 7.971 ops/ms
Iteration   3: 8.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.168 ±(99.9%) 4.912 ops/ms [Average]
  (min, avg, max) = (7.971, 8.168, 8.475), stdev = 0.269
  CI (99.9%): [3.256, 13.080] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.527 ops/ms
# Warmup Iteration   2: 7.347 ops/ms
# Warmup Iteration   3: 8.495 ops/ms
Iteration   1: 9.005 ops/ms
Iteration   2: 9.054 ops/ms
Iteration   3: 8.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.938 ±(99.9%) 2.939 ops/ms [Average]
  (min, avg, max) = (8.754, 8.938, 9.054), stdev = 0.161
  CI (99.9%): [5.998, 11.877] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.618 ops/ms
# Warmup Iteration   2: 7.204 ops/ms
# Warmup Iteration   3: 8.017 ops/ms
Iteration   1: 8.069 ops/ms
Iteration   2: 8.465 ops/ms
Iteration   3: 8.492 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.342 ±(99.9%) 4.322 ops/ms [Average]
  (min, avg, max) = (8.069, 8.342, 8.492), stdev = 0.237
  CI (99.9%): [4.020, 12.664] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.385 ops/ms
# Warmup Iteration   2: 6.062 ops/ms
# Warmup Iteration   3: 6.959 ops/ms
Iteration   1: 6.529 ops/ms
Iteration   2: 7.214 ops/ms
Iteration   3: 7.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.978 ±(99.9%) 7.087 ops/ms [Average]
  (min, avg, max) = (6.529, 6.978, 7.214), stdev = 0.388
  CI (99.9%): [≈ 0, 14.064] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 13.049 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.328 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.059 ±(99.9%) 0.006 ms/op
Iteration   1: 3.959 ±(99.9%) 0.011 ms/op
Iteration   2: 3.757 ±(99.9%) 0.013 ms/op
Iteration   3: 3.770 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.829 ±(99.9%) 2.057 ms/op [Average]
  (min, avg, max) = (3.757, 3.829, 3.959), stdev = 0.113
  CI (99.9%): [1.771, 5.886] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 10.363 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.327 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.719 ±(99.9%) 0.010 ms/op
Iteration   1: 3.654 ±(99.9%) 0.011 ms/op
Iteration   2: 3.664 ±(99.9%) 0.010 ms/op
Iteration   3: 3.765 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.694 ±(99.9%) 1.121 ms/op [Average]
  (min, avg, max) = (3.654, 3.694, 3.765), stdev = 0.061
  CI (99.9%): [2.573, 4.815] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 13.012 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.291 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.975 ±(99.9%) 0.012 ms/op
Iteration   1: 3.802 ±(99.9%) 0.013 ms/op
Iteration   2: 3.836 ±(99.9%) 0.010 ms/op
Iteration   3: 3.956 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.865 ±(99.9%) 1.477 ms/op [Average]
  (min, avg, max) = (3.802, 3.865, 3.956), stdev = 0.081
  CI (99.9%): [2.388, 5.342] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.966 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.115 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.466 ±(99.9%) 0.012 ms/op
Iteration   1: 4.561 ±(99.9%) 0.008 ms/op
Iteration   2: 4.531 ±(99.9%) 0.011 ms/op
Iteration   3: 4.550 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.547 ±(99.9%) 0.272 ms/op [Average]
  (min, avg, max) = (4.531, 4.547, 4.561), stdev = 0.015
  CI (99.9%): [4.275, 4.820] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.071 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 4.790 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.164 ±(99.9%) 0.017 ms/op
Iteration   1: 3.780 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.722 ms/op
                 createUser·p0.50:   3.617 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   7.676 ms/op
                 createUser·p0.999:  23.442 ms/op
                 createUser·p0.9999: 27.250 ms/op
                 createUser·p1.00:   28.508 ms/op

Iteration   2: 3.825 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.391 ms/op
                 createUser·p0.50:   3.658 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.858 ms/op
                 createUser·p0.99:   6.291 ms/op
                 createUser·p0.999:  24.400 ms/op
                 createUser·p0.9999: 28.349 ms/op
                 createUser·p1.00:   29.852 ms/op

Iteration   3: 3.844 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.396 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   5.243 ms/op
                 createUser·p0.99:   8.585 ms/op
                 createUser·p0.999:  22.285 ms/op
                 createUser·p0.9999: 29.196 ms/op
                 createUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 251679
  mean =      3.816 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 748 
    [ 2.500,  5.000) = 239966 
    [ 5.000,  7.500) = 7892 
    [ 7.500, 10.000) = 2235 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 119 

  Percentiles, ms/op:
      p(0.0000) =      0.396 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      7.807 ms/op
     p(99.9000) =     23.331 ms/op
     p(99.9900) =     28.705 ms/op
     p(99.9990) =     29.750 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.946 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 3.999 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.778 ±(99.9%) 0.011 ms/op
Iteration   1: 3.953 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.153 ms/op
                 existUser·p0.50:   3.785 ms/op
                 existUser·p0.90:   4.694 ms/op
                 existUser·p0.95:   5.145 ms/op
                 existUser·p0.99:   6.808 ms/op
                 existUser·p0.999:  13.386 ms/op
                 existUser·p0.9999: 29.968 ms/op
                 existUser·p1.00:   30.671 ms/op

Iteration   2: 3.713 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.806 ms/op
                 existUser·p0.50:   3.609 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   6.568 ms/op
                 existUser·p0.999:  9.413 ms/op
                 existUser·p0.9999: 27.354 ms/op
                 existUser·p1.00:   27.754 ms/op

Iteration   3: 3.599 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.561 ms/op
                 existUser·p0.50:   3.465 ms/op
                 existUser·p0.90:   4.051 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   6.562 ms/op
                 existUser·p0.999:  25.859 ms/op
                 existUser·p0.9999: 31.756 ms/op
                 existUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 255857
  mean =      3.749 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1278 
    [ 2.500,  5.000) = 243648 
    [ 5.000,  7.500) = 9832 
    [ 7.500, 10.000) = 696 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 58 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     13.126 ms/op
     p(99.9900) =     31.307 ms/op
     p(99.9990) =     32.043 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 11.796 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.257 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.013 ms/op
Iteration   1: 4.077 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.837 ms/op
                 getUser·p0.50:   3.838 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   6.341 ms/op
                 getUser·p0.99:   8.815 ms/op
                 getUser·p0.999:  17.713 ms/op
                 getUser·p0.9999: 22.875 ms/op
                 getUser·p1.00:   23.691 ms/op

Iteration   2: 4.000 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.542 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   5.087 ms/op
                 getUser·p0.99:   8.036 ms/op
                 getUser·p0.999:  12.386 ms/op
                 getUser·p0.9999: 31.752 ms/op
                 getUser·p1.00:   31.949 ms/op

Iteration   3: 3.823 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.311 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  25.011 ms/op
                 getUser·p0.9999: 27.644 ms/op
                 getUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 242158
  mean =      3.964 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 382 
    [ 2.500,  5.000) = 227720 
    [ 5.000,  7.500) = 10583 
    [ 7.500, 10.000) = 2483 
    [10.000, 12.500) = 617 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      5.333 ms/op
     p(99.0000) =      7.930 ms/op
     p(99.9000) =     17.586 ms/op
     p(99.9900) =     30.434 ms/op
     p(99.9990) =     31.888 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.497 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 5.044 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.619 ±(99.9%) 0.015 ms/op
Iteration   1: 4.587 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  24.911 ms/op
                 listUser·p0.9999: 29.625 ms/op
                 listUser·p1.00:   30.212 ms/op

Iteration   2: 4.482 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.482 ms/op
                 listUser·p0.50:   4.358 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   7.991 ms/op
                 listUser·p0.999:  16.663 ms/op
                 listUser·p0.9999: 23.682 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   3: 4.357 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.589 ms/op
                 listUser·p0.50:   4.243 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.177 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  16.007 ms/op
                 listUser·p0.9999: 17.465 ms/op
                 listUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 214630
  mean =      4.473 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 192589 
    [ 5.000,  7.500) = 18684 
    [ 7.500, 10.000) = 2561 
    [10.000, 12.500) = 298 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 203 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.589 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.431 ms/op
     p(99.0000) =      7.963 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     28.821 ms/op
     p(99.9990) =     29.945 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.168 ± 4.912  ops/ms
ClientPb.existUser                       thrpt       3   8.938 ± 2.939  ops/ms
ClientPb.getUser                         thrpt       3   8.342 ± 4.322  ops/ms
ClientPb.listUser                        thrpt       3   6.978 ± 7.087  ops/ms
ClientPb.createUser                       avgt       3   3.829 ± 2.057   ms/op
ClientPb.existUser                        avgt       3   3.694 ± 1.121   ms/op
ClientPb.getUser                          avgt       3   3.865 ± 1.477   ms/op
ClientPb.listUser                         avgt       3   4.547 ± 0.272   ms/op
ClientPb.createUser                     sample  251679   3.816 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.396           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.654           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.334           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.866           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.807           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.331           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.705           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.884           ms/op
ClientPb.existUser                      sample  255857   3.749 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.153           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.440           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.874           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.644           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.126           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.307           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.539           ms/op
ClientPb.getUser                        sample  242158   3.964 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.311           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.407           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.333           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.930           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.586           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.434           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.949           ms/op
ClientPb.listUser                       sample  214630   4.473 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.589           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.014           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.431           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.963           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.465           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.821           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.212           ms/op
