# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.911 ops/ms
# Warmup Iteration   2: 4.949 ops/ms
# Warmup Iteration   3: 8.287 ops/ms
Iteration   1: 9.021 ops/ms
Iteration   2: 8.427 ops/ms
Iteration   3: 8.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.766 ±(99.9%) 5.581 ops/ms [Average]
  (min, avg, max) = (8.427, 8.766, 9.021), stdev = 0.306
  CI (99.9%): [3.185, 14.347] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.782 ops/ms
# Warmup Iteration   2: 8.482 ops/ms
# Warmup Iteration   3: 9.485 ops/ms
Iteration   1: 9.633 ops/ms
Iteration   2: 9.635 ops/ms
Iteration   3: 9.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.578 ±(99.9%) 1.757 ops/ms [Average]
  (min, avg, max) = (9.467, 9.578, 9.635), stdev = 0.096
  CI (99.9%): [7.821, 11.335] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.793 ops/ms
# Warmup Iteration   2: 7.601 ops/ms
# Warmup Iteration   3: 8.469 ops/ms
Iteration   1: 8.682 ops/ms
Iteration   2: 9.154 ops/ms
Iteration   3: 9.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.993 ±(99.9%) 4.908 ops/ms [Average]
  (min, avg, max) = (8.682, 8.993, 9.154), stdev = 0.269
  CI (99.9%): [4.085, 13.901] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.491 ops/ms
# Warmup Iteration   2: 6.763 ops/ms
# Warmup Iteration   3: 7.476 ops/ms
Iteration   1: 7.492 ops/ms
Iteration   2: 7.532 ops/ms
Iteration   3: 7.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.565 ±(99.9%) 1.715 ops/ms [Average]
  (min, avg, max) = (7.492, 7.565, 7.671), stdev = 0.094
  CI (99.9%): [5.850, 9.280] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.434 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.143 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.693 ±(99.9%) 0.005 ms/op
Iteration   1: 3.640 ±(99.9%) 0.006 ms/op
Iteration   2: 3.620 ±(99.9%) 0.006 ms/op
Iteration   3: 3.636 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.632 ±(99.9%) 0.194 ms/op [Average]
  (min, avg, max) = (3.620, 3.632, 3.640), stdev = 0.011
  CI (99.9%): [3.438, 3.826] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.456 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.737 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.524 ±(99.9%) 0.004 ms/op
Iteration   1: 3.433 ±(99.9%) 0.005 ms/op
Iteration   2: 3.408 ±(99.9%) 0.004 ms/op
Iteration   3: 3.406 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.415 ±(99.9%) 0.270 ms/op [Average]
  (min, avg, max) = (3.406, 3.415, 3.433), stdev = 0.015
  CI (99.9%): [3.145, 3.686] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.645 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.969 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.587 ±(99.9%) 0.006 ms/op
Iteration   1: 3.665 ±(99.9%) 0.003 ms/op
Iteration   2: 3.546 ±(99.9%) 0.006 ms/op
Iteration   3: 3.461 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.558 ±(99.9%) 1.871 ms/op [Average]
  (min, avg, max) = (3.461, 3.558, 3.665), stdev = 0.103
  CI (99.9%): [1.687, 5.428] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.860 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.668 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.233 ±(99.9%) 0.008 ms/op
Iteration   1: 4.329 ±(99.9%) 0.007 ms/op
Iteration   2: 4.076 ±(99.9%) 0.012 ms/op
Iteration   3: 4.036 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.147 ±(99.9%) 2.905 ms/op [Average]
  (min, avg, max) = (4.036, 4.147, 4.329), stdev = 0.159
  CI (99.9%): [1.242, 7.052] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.886 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.233 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.620 ±(99.9%) 0.012 ms/op
Iteration   1: 3.620 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.792 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.956 ms/op
                 createUser·p0.99:   7.356 ms/op
                 createUser·p0.999:  22.760 ms/op
                 createUser·p0.9999: 26.094 ms/op
                 createUser·p1.00:   26.804 ms/op

Iteration   2: 3.707 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.378 ms/op
                 createUser·p0.50:   3.518 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.751 ms/op
                 createUser·p0.99:   6.906 ms/op
                 createUser·p0.999:  12.894 ms/op
                 createUser·p0.9999: 26.706 ms/op
                 createUser·p1.00:   27.722 ms/op

Iteration   3: 3.543 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.163 ms/op
                 createUser·p0.50:   3.486 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  23.583 ms/op
                 createUser·p0.9999: 34.140 ms/op
                 createUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 265109
  mean =      3.622 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2093 
    [ 2.500,  5.000) = 252858 
    [ 5.000,  7.500) = 8410 
    [ 7.500, 10.000) = 1111 
    [10.000, 12.500) = 281 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 103 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     17.003 ms/op
     p(99.9900) =     32.668 ms/op
     p(99.9990) =     34.806 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.093 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.796 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.441 ±(99.9%) 0.009 ms/op
Iteration   1: 3.366 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.714 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.669 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   6.504 ms/op
                 existUser·p0.999:  21.641 ms/op
                 existUser·p0.9999: 24.379 ms/op
                 existUser·p1.00:   25.625 ms/op

Iteration   2: 3.367 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.786 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   6.177 ms/op
                 existUser·p0.999:  22.320 ms/op
                 existUser·p0.9999: 32.211 ms/op
                 existUser·p1.00:   33.620 ms/op

Iteration   3: 3.550 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.710 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   4.121 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   7.234 ms/op
                 existUser·p0.999:  23.589 ms/op
                 existUser·p0.9999: 28.803 ms/op
                 existUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279945
  mean =      3.425 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3316 
    [ 2.500,  5.000) = 267891 
    [ 5.000,  7.500) = 6917 
    [ 7.500, 10.000) = 1052 
    [10.000, 12.500) = 349 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 124 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.710 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.339 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     21.825 ms/op
     p(99.9900) =     31.490 ms/op
     p(99.9990) =     32.906 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.140 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.915 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.010 ms/op
Iteration   1: 3.664 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.243 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   4.306 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   7.143 ms/op
                 getUser·p0.999:  13.353 ms/op
                 getUser·p0.9999: 26.079 ms/op
                 getUser·p1.00:   27.722 ms/op

Iteration   2: 3.485 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.745 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   6.297 ms/op
                 getUser·p0.999:  23.620 ms/op
                 getUser·p0.9999: 26.373 ms/op
                 getUser·p1.00:   27.361 ms/op

Iteration   3: 3.561 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.239 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   4.018 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   7.807 ms/op
                 getUser·p0.999:  23.537 ms/op
                 getUser·p0.9999: 29.917 ms/op
                 getUser·p1.00:   30.966 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 268738
  mean =      3.568 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4270 
    [ 2.500,  5.000) = 254569 
    [ 5.000,  7.500) = 7628 
    [ 7.500, 10.000) = 1450 
    [10.000, 12.500) = 472 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 116 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.239 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     16.761 ms/op
     p(99.9900) =     28.545 ms/op
     p(99.9990) =     30.831 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.578 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.552 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.335 ±(99.9%) 0.016 ms/op
Iteration   1: 4.176 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.919 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   7.782 ms/op
                 listUser·p0.999:  22.334 ms/op
                 listUser·p0.9999: 26.203 ms/op
                 listUser·p1.00:   26.935 ms/op

Iteration   2: 4.342 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.470 ms/op
                 listUser·p0.50:   4.227 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   8.459 ms/op
                 listUser·p0.999:  16.275 ms/op
                 listUser·p0.9999: 19.595 ms/op
                 listUser·p1.00:   19.726 ms/op

Iteration   3: 4.240 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.544 ms/op
                 listUser·p0.50:   4.051 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   8.061 ms/op
                 listUser·p0.999:  18.161 ms/op
                 listUser·p0.9999: 21.987 ms/op
                 listUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 225755
  mean =      4.252 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 211431 
    [ 5.000,  7.500) = 11102 
    [ 7.500, 10.000) = 2187 
    [10.000, 12.500) = 527 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.919 ms/op
     p(50.0000) =      4.063 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.194 ms/op
     p(99.0000) =      8.110 ms/op
     p(99.9000) =     18.874 ms/op
     p(99.9900) =     25.788 ms/op
     p(99.9990) =     26.444 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.766 ± 5.581  ops/ms
ClientPb.existUser                       thrpt       3   9.578 ± 1.757  ops/ms
ClientPb.getUser                         thrpt       3   8.993 ± 4.908  ops/ms
ClientPb.listUser                        thrpt       3   7.565 ± 1.715  ops/ms
ClientPb.createUser                       avgt       3   3.632 ± 0.194   ms/op
ClientPb.existUser                        avgt       3   3.415 ± 0.270   ms/op
ClientPb.getUser                          avgt       3   3.558 ± 1.871   ms/op
ClientPb.listUser                         avgt       3   4.147 ± 2.905   ms/op
ClientPb.createUser                     sample  265109   3.622 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.163           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.461           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.104           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.571           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.988           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.003           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.668           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.062           ms/op
ClientPb.existUser                      sample  279945   3.425 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.710           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.256           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.339           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.709           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.825           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.490           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.620           ms/op
ClientPb.getUser                        sample  268738   3.568 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.239           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.371           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.530           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.127           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.761           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.545           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.966           ms/op
ClientPb.listUser                       sample  225755   4.252 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.919           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.063           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.194           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.110           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.874           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.788           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.935           ms/op
