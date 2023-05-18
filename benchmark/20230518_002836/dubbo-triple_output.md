# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.983 ops/ms
# Warmup Iteration   2: 4.754 ops/ms
# Warmup Iteration   3: 8.552 ops/ms
Iteration   1: 9.218 ops/ms
Iteration   2: 9.206 ops/ms
Iteration   3: 8.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.077 ±(99.9%) 4.278 ops/ms [Average]
  (min, avg, max) = (8.806, 9.077, 9.218), stdev = 0.234
  CI (99.9%): [4.799, 13.355] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.674 ops/ms
# Warmup Iteration   2: 7.883 ops/ms
# Warmup Iteration   3: 9.186 ops/ms
Iteration   1: 9.228 ops/ms
Iteration   2: 9.928 ops/ms
Iteration   3: 9.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.603 ±(99.9%) 6.430 ops/ms [Average]
  (min, avg, max) = (9.228, 9.603, 9.928), stdev = 0.352
  CI (99.9%): [3.172, 16.033] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.392 ops/ms
# Warmup Iteration   2: 7.894 ops/ms
# Warmup Iteration   3: 9.190 ops/ms
Iteration   1: 9.348 ops/ms
Iteration   2: 9.092 ops/ms
Iteration   3: 8.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.064 ±(99.9%) 5.460 ops/ms [Average]
  (min, avg, max) = (8.751, 9.064, 9.348), stdev = 0.299
  CI (99.9%): [3.604, 14.523] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.856 ops/ms
# Warmup Iteration   2: 7.327 ops/ms
# Warmup Iteration   3: 7.926 ops/ms
Iteration   1: 7.744 ops/ms
Iteration   2: 8.159 ops/ms
Iteration   3: 7.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.926 ±(99.9%) 3.876 ops/ms [Average]
  (min, avg, max) = (7.744, 7.926, 8.159), stdev = 0.212
  CI (99.9%): [4.049, 11.802] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.896 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.874 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.594 ±(99.9%) 0.011 ms/op
Iteration   1: 3.380 ±(99.9%) 0.009 ms/op
Iteration   2: 3.529 ±(99.9%) 0.007 ms/op
Iteration   3: 3.430 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.446 ±(99.9%) 1.385 ms/op [Average]
  (min, avg, max) = (3.380, 3.446, 3.529), stdev = 0.076
  CI (99.9%): [2.061, 4.832] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 9.955 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.685 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.323 ±(99.9%) 0.006 ms/op
Iteration   1: 3.262 ±(99.9%) 0.004 ms/op
Iteration   2: 3.411 ±(99.9%) 0.003 ms/op
Iteration   3: 3.304 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.326 ±(99.9%) 1.400 ms/op [Average]
  (min, avg, max) = (3.262, 3.326, 3.411), stdev = 0.077
  CI (99.9%): [1.926, 4.726] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.709 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.809 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.599 ±(99.9%) 0.005 ms/op
Iteration   1: 3.467 ±(99.9%) 0.007 ms/op
Iteration   2: 3.590 ±(99.9%) 0.006 ms/op
Iteration   3: 3.381 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.479 ±(99.9%) 1.916 ms/op [Average]
  (min, avg, max) = (3.381, 3.479, 3.590), stdev = 0.105
  CI (99.9%): [1.563, 5.395] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 12.057 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.396 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.123 ±(99.9%) 0.010 ms/op
Iteration   1: 4.014 ±(99.9%) 0.015 ms/op
Iteration   2: 4.075 ±(99.9%) 0.011 ms/op
Iteration   3: 3.929 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.006 ±(99.9%) 1.337 ms/op [Average]
  (min, avg, max) = (3.929, 4.006, 4.075), stdev = 0.073
  CI (99.9%): [2.669, 5.343] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.230 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.008 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.010 ms/op
Iteration   1: 3.748 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   6.971 ms/op
                 createUser·p0.99:   7.930 ms/op
                 createUser·p0.999:  11.600 ms/op
                 createUser·p0.9999: 23.200 ms/op
                 createUser·p1.00:   24.576 ms/op

Iteration   2: 3.407 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.386 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  22.031 ms/op
                 createUser·p0.9999: 24.400 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   3: 3.506 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.516 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  23.985 ms/op
                 createUser·p0.9999: 27.918 ms/op
                 createUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270328
  mean =      3.548 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11729 
    [ 2.500,  5.000) = 246061 
    [ 5.000,  7.500) = 9838 
    [ 7.500, 10.000) = 2240 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 137 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     20.295 ms/op
     p(99.9900) =     25.951 ms/op
     p(99.9990) =     32.408 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 10.973 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 3.859 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.388 ±(99.9%) 0.009 ms/op
Iteration   1: 3.335 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.417 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  16.271 ms/op
                 existUser·p0.9999: 22.525 ms/op
                 existUser·p1.00:   23.167 ms/op

Iteration   2: 3.320 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.128 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  15.680 ms/op
                 existUser·p0.9999: 25.526 ms/op
                 existUser·p1.00:   27.066 ms/op

Iteration   3: 3.509 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.620 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   4.100 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   7.109 ms/op
                 existUser·p0.999:  10.926 ms/op
                 existUser·p0.9999: 28.144 ms/op
                 existUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283385
  mean =      3.386 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5372 
    [ 2.500,  5.000) = 271054 
    [ 5.000,  7.500) = 5883 
    [ 7.500, 10.000) = 632 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     11.846 ms/op
     p(99.9900) =     26.608 ms/op
     p(99.9990) =     28.514 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.258 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.448 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.476 ±(99.9%) 0.009 ms/op
Iteration   1: 3.486 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.350 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  20.825 ms/op
                 getUser·p0.9999: 23.233 ms/op
                 getUser·p1.00:   24.117 ms/op

Iteration   2: 3.530 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.993 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   7.471 ms/op
                 getUser·p0.999:  22.053 ms/op
                 getUser·p0.9999: 32.997 ms/op
                 getUser·p1.00:   33.620 ms/op

Iteration   3: 3.541 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.989 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.043 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   6.259 ms/op
                 getUser·p0.999:  11.911 ms/op
                 getUser·p0.9999: 27.197 ms/op
                 getUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272754
  mean =      3.519 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1910 
    [ 2.500,  5.000) = 260278 
    [ 5.000,  7.500) = 8822 
    [ 7.500, 10.000) = 1134 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.989 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     18.285 ms/op
     p(99.9900) =     30.638 ms/op
     p(99.9990) =     33.459 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.541 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.493 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.137 ±(99.9%) 0.012 ms/op
Iteration   1: 4.175 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.763 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  20.594 ms/op
                 listUser·p0.9999: 26.390 ms/op
                 listUser·p1.00:   27.361 ms/op

Iteration   2: 4.022 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.413 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.936 ms/op
                 listUser·p0.999:  15.425 ms/op
                 listUser·p0.9999: 17.708 ms/op
                 listUser·p1.00:   19.988 ms/op

Iteration   3: 3.991 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.462 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  15.875 ms/op
                 listUser·p0.9999: 20.087 ms/op
                 listUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236075
  mean =      4.061 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 227854 
    [ 5.000,  7.500) = 5564 
    [ 7.500, 10.000) = 1696 
    [10.000, 12.500) = 395 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.763 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.750 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     25.190 ms/op
     p(99.9990) =     26.960 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.077 ± 4.278  ops/ms
ClientPb.existUser                       thrpt       3   9.603 ± 6.430  ops/ms
ClientPb.getUser                         thrpt       3   9.064 ± 5.460  ops/ms
ClientPb.listUser                        thrpt       3   7.926 ± 3.876  ops/ms
ClientPb.createUser                       avgt       3   3.446 ± 1.385   ms/op
ClientPb.existUser                        avgt       3   3.326 ± 1.400   ms/op
ClientPb.getUser                          avgt       3   3.479 ± 1.916   ms/op
ClientPb.listUser                         avgt       3   4.006 ± 1.337   ms/op
ClientPb.createUser                     sample  270328   3.548 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.190           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.400           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.994           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.776           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.496           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.295           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.951           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.440           ms/op
ClientPb.existUser                      sample  283385   3.386 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.128           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.243           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.038           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.846           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.608           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.098           ms/op
ClientPb.getUser                        sample  272754   3.519 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.989           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.415           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.037           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.285           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.638           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.620           ms/op
ClientPb.listUser                       sample  236075   4.061 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.763           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.750           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.876           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.190           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.361           ms/op
