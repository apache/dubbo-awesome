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
# Warmup Iteration   1: 2.095 ops/ms
# Warmup Iteration   2: 5.533 ops/ms
# Warmup Iteration   3: 8.499 ops/ms
Iteration   1: 8.970 ops/ms
Iteration   2: 9.334 ops/ms
Iteration   3: 9.428 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.244 ±(99.9%) 4.412 ops/ms [Average]
  (min, avg, max) = (8.970, 9.244, 9.428), stdev = 0.242
  CI (99.9%): [4.832, 13.657] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.868 ops/ms
# Warmup Iteration   2: 8.794 ops/ms
# Warmup Iteration   3: 9.112 ops/ms
Iteration   1: 9.858 ops/ms
Iteration   2: 9.905 ops/ms
Iteration   3: 9.986 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.916 ±(99.9%) 1.180 ops/ms [Average]
  (min, avg, max) = (9.858, 9.916, 9.986), stdev = 0.065
  CI (99.9%): [8.736, 11.097] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.131 ops/ms
# Warmup Iteration   2: 7.769 ops/ms
# Warmup Iteration   3: 8.922 ops/ms
Iteration   1: 9.049 ops/ms
Iteration   2: 9.368 ops/ms
Iteration   3: 9.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.341 ±(99.9%) 5.113 ops/ms [Average]
  (min, avg, max) = (9.049, 9.341, 9.608), stdev = 0.280
  CI (99.9%): [4.228, 14.455] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.811 ops/ms
# Warmup Iteration   2: 7.533 ops/ms
# Warmup Iteration   3: 7.572 ops/ms
Iteration   1: 8.195 ops/ms
Iteration   2: 7.955 ops/ms
Iteration   3: 8.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.050 ±(99.9%) 2.332 ops/ms [Average]
  (min, avg, max) = (7.955, 8.050, 8.195), stdev = 0.128
  CI (99.9%): [5.718, 10.382] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.649 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.068 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.528 ±(99.9%) 0.007 ms/op
Iteration   1: 3.406 ±(99.9%) 0.014 ms/op
Iteration   2: 3.382 ±(99.9%) 0.012 ms/op
Iteration   3: 3.385 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.391 ±(99.9%) 0.241 ms/op [Average]
  (min, avg, max) = (3.382, 3.391, 3.406), stdev = 0.013
  CI (99.9%): [3.150, 3.631] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.650 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.622 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.003 ms/op
Iteration   1: 3.194 ±(99.9%) 0.009 ms/op
Iteration   2: 3.243 ±(99.9%) 0.009 ms/op
Iteration   3: 3.179 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.205 ±(99.9%) 0.614 ms/op [Average]
  (min, avg, max) = (3.179, 3.205, 3.243), stdev = 0.034
  CI (99.9%): [2.592, 3.819] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.428 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.742 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.457 ±(99.9%) 0.011 ms/op
Iteration   1: 3.400 ±(99.9%) 0.008 ms/op
Iteration   2: 3.579 ±(99.9%) 0.007 ms/op
Iteration   3: 3.384 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.454 ±(99.9%) 1.975 ms/op [Average]
  (min, avg, max) = (3.384, 3.454, 3.579), stdev = 0.108
  CI (99.9%): [1.479, 5.429] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.774 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.385 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.156 ±(99.9%) 0.010 ms/op
Iteration   1: 3.995 ±(99.9%) 0.017 ms/op
Iteration   2: 3.925 ±(99.9%) 0.016 ms/op
Iteration   3: 3.823 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.914 ±(99.9%) 1.584 ms/op [Average]
  (min, avg, max) = (3.823, 3.914, 3.995), stdev = 0.087
  CI (99.9%): [2.330, 5.499] (assumes normal distribution)


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
# Warmup Iteration   1: 9.783 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.992 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.472 ±(99.9%) 0.010 ms/op
Iteration   1: 3.465 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.767 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  21.327 ms/op
                 createUser·p0.9999: 25.847 ms/op
                 createUser·p1.00:   26.345 ms/op

Iteration   2: 3.417 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.212 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   5.844 ms/op
                 createUser·p0.999:  22.162 ms/op
                 createUser·p0.9999: 29.098 ms/op
                 createUser·p1.00:   30.343 ms/op

Iteration   3: 3.633 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.743 ms/op
                 createUser·p0.95:   4.981 ms/op
                 createUser·p0.99:   6.046 ms/op
                 createUser·p0.999:  20.447 ms/op
                 createUser·p0.9999: 36.962 ms/op
                 createUser·p1.00:   37.028 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273989
  mean =      3.503 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7244 
    [ 2.500,  5.000) = 259033 
    [ 5.000,  7.500) = 6675 
    [ 7.500, 10.000) = 560 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     20.907 ms/op
     p(99.9900) =     35.442 ms/op
     p(99.9990) =     37.028 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.995 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.664 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.384 ±(99.9%) 0.009 ms/op
Iteration   1: 3.287 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.151 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  10.765 ms/op
                 existUser·p0.9999: 23.274 ms/op
                 existUser·p1.00:   23.658 ms/op

Iteration   2: 3.322 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.229 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  19.629 ms/op
                 existUser·p0.9999: 25.690 ms/op
                 existUser·p1.00:   26.640 ms/op

Iteration   3: 3.422 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.171 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.920 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   5.704 ms/op
                 existUser·p0.999:  11.141 ms/op
                 existUser·p0.9999: 27.875 ms/op
                 existUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286957
  mean =      3.343 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11795 
    [ 2.500,  5.000) = 269781 
    [ 5.000,  7.500) = 4587 
    [ 7.500, 10.000) = 407 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.151 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     13.156 ms/op
     p(99.9900) =     26.585 ms/op
     p(99.9990) =     28.381 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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
# Warmup Iteration   1: 8.787 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.727 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.532 ±(99.9%) 0.012 ms/op
Iteration   1: 3.524 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.571 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   5.177 ms/op
                 getUser·p0.99:   7.291 ms/op
                 getUser·p0.999:  22.020 ms/op
                 getUser·p0.9999: 26.572 ms/op
                 getUser·p1.00:   27.591 ms/op

Iteration   2: 3.442 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.139 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  22.905 ms/op
                 getUser·p0.9999: 31.546 ms/op
                 getUser·p1.00:   32.047 ms/op

Iteration   3: 3.439 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.591 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.170 ms/op
                 getUser·p0.99:   6.521 ms/op
                 getUser·p0.999:  9.716 ms/op
                 getUser·p0.9999: 35.723 ms/op
                 getUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276486
  mean =      3.468 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7987 
    [ 2.500,  5.000) = 260346 
    [ 5.000,  7.500) = 6697 
    [ 7.500, 10.000) = 1154 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     10.437 ms/op
     p(99.9900) =     33.344 ms/op
     p(99.9990) =     36.110 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


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
# Warmup Iteration   1: 10.123 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.512 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.089 ±(99.9%) 0.012 ms/op
Iteration   1: 4.178 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.974 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.177 ms/op
                 listUser·p0.99:   8.045 ms/op
                 listUser·p0.999:  18.915 ms/op
                 listUser·p0.9999: 25.166 ms/op
                 listUser·p1.00:   26.968 ms/op

Iteration   2: 4.060 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  15.163 ms/op
                 listUser·p0.9999: 18.878 ms/op
                 listUser·p1.00:   19.202 ms/op

Iteration   3: 3.937 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   6.350 ms/op
                 listUser·p0.999:  15.020 ms/op
                 listUser·p0.9999: 18.022 ms/op
                 listUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236628
  mean =      4.056 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 226857 
    [ 5.000,  7.500) = 7450 
    [ 7.500, 10.000) = 1469 
    [10.000, 12.500) = 297 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.974 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.438 ms/op
     p(99.9000) =     16.581 ms/op
     p(99.9900) =     23.451 ms/op
     p(99.9990) =     26.596 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.244 ± 4.412  ops/ms
ClientPb.existUser                       thrpt       3   9.916 ± 1.180  ops/ms
ClientPb.getUser                         thrpt       3   9.341 ± 5.113  ops/ms
ClientPb.listUser                        thrpt       3   8.050 ± 2.332  ops/ms
ClientPb.createUser                       avgt       3   3.391 ± 0.241   ms/op
ClientPb.existUser                        avgt       3   3.205 ± 0.614   ms/op
ClientPb.getUser                          avgt       3   3.454 ± 1.975   ms/op
ClientPb.listUser                         avgt       3   3.914 ± 1.584   ms/op
ClientPb.createUser                     sample  273989   3.503 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.859           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.063           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.735           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.964           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.907           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.442           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.028           ms/op
ClientPb.existUser                      sample  286957   3.343 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.151           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.521           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.156           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.585           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.705           ms/op
ClientPb.getUser                        sample  276486   3.468 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.139           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.202           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.062           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.437           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.344           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.110           ms/op
ClientPb.listUser                       sample  236628   4.056 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.974           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.891           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.438           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.581           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.451           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.968           ms/op
