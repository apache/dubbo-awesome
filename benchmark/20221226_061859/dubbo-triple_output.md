# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.956 ops/ms
# Warmup Iteration   2: 2.300 ops/ms
# Warmup Iteration   3: 4.954 ops/ms
Iteration   1: 5.551 ops/ms
Iteration   2: 5.944 ops/ms
Iteration   3: 5.902 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.799 ±(99.9%) 3.936 ops/ms [Average]
  (min, avg, max) = (5.551, 5.799, 5.944), stdev = 0.216
  CI (99.9%): [1.863, 9.735] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.588 ops/ms
# Warmup Iteration   2: 4.836 ops/ms
# Warmup Iteration   3: 5.929 ops/ms
Iteration   1: 6.465 ops/ms
Iteration   2: 6.371 ops/ms
Iteration   3: 6.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.314 ±(99.9%) 3.402 ops/ms [Average]
  (min, avg, max) = (6.105, 6.314, 6.465), stdev = 0.186
  CI (99.9%): [2.911, 9.716] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.804 ops/ms
# Warmup Iteration   2: 4.517 ops/ms
# Warmup Iteration   3: 5.935 ops/ms
Iteration   1: 5.850 ops/ms
Iteration   2: 5.917 ops/ms
Iteration   3: 5.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.826 ±(99.9%) 1.910 ops/ms [Average]
  (min, avg, max) = (5.712, 5.826, 5.917), stdev = 0.105
  CI (99.9%): [3.916, 7.737] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 1.633 ops/ms
# Warmup Iteration   2: 3.759 ops/ms
# Warmup Iteration   3: 4.935 ops/ms
Iteration   1: 4.689 ops/ms
Iteration   2: 5.026 ops/ms
Iteration   3: 4.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.896 ±(99.9%) 3.311 ops/ms [Average]
  (min, avg, max) = (4.689, 4.896, 5.026), stdev = 0.181
  CI (99.9%): [1.585, 8.207] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 18.635 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 7.005 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.511 ±(99.9%) 0.017 ms/op
Iteration   1: 5.372 ±(99.9%) 0.017 ms/op
Iteration   2: 5.442 ±(99.9%) 0.008 ms/op
Iteration   3: 5.596 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.470 ±(99.9%) 2.094 ms/op [Average]
  (min, avg, max) = (5.372, 5.470, 5.596), stdev = 0.115
  CI (99.9%): [3.375, 7.564] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 19.324 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 6.834 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.462 ±(99.9%) 0.009 ms/op
Iteration   1: 5.274 ±(99.9%) 0.006 ms/op
Iteration   2: 5.076 ±(99.9%) 0.014 ms/op
Iteration   3: 5.242 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.197 ±(99.9%) 1.939 ms/op [Average]
  (min, avg, max) = (5.076, 5.197, 5.274), stdev = 0.106
  CI (99.9%): [3.258, 7.136] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 18.510 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 6.382 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.413 ±(99.9%) 0.009 ms/op
Iteration   1: 5.467 ±(99.9%) 0.010 ms/op
Iteration   2: 5.273 ±(99.9%) 0.010 ms/op
Iteration   3: 5.374 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.371 ±(99.9%) 1.766 ms/op [Average]
  (min, avg, max) = (5.273, 5.371, 5.467), stdev = 0.097
  CI (99.9%): [3.605, 7.138] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 20.697 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 8.176 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.667 ±(99.9%) 0.009 ms/op
Iteration   1: 6.442 ±(99.9%) 0.011 ms/op
Iteration   2: 6.411 ±(99.9%) 0.016 ms/op
Iteration   3: 6.528 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.460 ±(99.9%) 1.100 ms/op [Average]
  (min, avg, max) = (6.411, 6.460, 6.528), stdev = 0.060
  CI (99.9%): [5.360, 7.561] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 17.668 ±(99.9%) 0.251 ms/op
# Warmup Iteration   2: 7.226 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.327 ±(99.9%) 0.034 ms/op
Iteration   1: 5.577 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.314 ms/op
                 createUser·p0.50:   5.292 ms/op
                 createUser·p0.90:   6.726 ms/op
                 createUser·p0.95:   7.809 ms/op
                 createUser·p0.99:   10.469 ms/op
                 createUser·p0.999:  24.955 ms/op
                 createUser·p0.9999: 27.435 ms/op
                 createUser·p1.00:   29.065 ms/op

Iteration   2: 5.351 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.490 ms/op
                 createUser·p0.50:   5.120 ms/op
                 createUser·p0.90:   6.242 ms/op
                 createUser·p0.95:   6.832 ms/op
                 createUser·p0.99:   9.617 ms/op
                 createUser·p0.999:  27.263 ms/op
                 createUser·p0.9999: 30.058 ms/op
                 createUser·p1.00:   30.638 ms/op

Iteration   3: 5.595 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.196 ms/op
                 createUser·p0.50:   5.218 ms/op
                 createUser·p0.90:   7.143 ms/op
                 createUser·p0.95:   7.938 ms/op
                 createUser·p0.99:   10.529 ms/op
                 createUser·p0.999:  26.144 ms/op
                 createUser·p0.9999: 31.944 ms/op
                 createUser·p1.00:   32.473 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 174210
  mean =      5.505 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 64552 
    [ 5.000,  7.500) = 100248 
    [ 7.500, 10.000) = 7475 
    [10.000, 12.500) = 1137 
    [12.500, 15.000) = 431 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      6.668 ms/op
     p(95.0000) =      7.606 ms/op
     p(99.0000) =     10.207 ms/op
     p(99.9000) =     25.919 ms/op
     p(99.9900) =     31.042 ms/op
     p(99.9990) =     32.449 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 18.359 ±(99.9%) 0.341 ms/op
# Warmup Iteration   2: 6.755 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.577 ±(99.9%) 0.024 ms/op
Iteration   1: 5.254 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.544 ms/op
                 existUser·p0.50:   4.932 ms/op
                 existUser·p0.90:   6.447 ms/op
                 existUser·p0.95:   7.766 ms/op
                 existUser·p0.99:   10.568 ms/op
                 existUser·p0.999:  27.761 ms/op
                 existUser·p0.9999: 33.316 ms/op
                 existUser·p1.00:   35.586 ms/op

Iteration   2: 5.311 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.503 ms/op
                 existUser·p0.50:   5.046 ms/op
                 existUser·p0.90:   6.472 ms/op
                 existUser·p0.95:   7.389 ms/op
                 existUser·p0.99:   9.515 ms/op
                 existUser·p0.999:  17.312 ms/op
                 existUser·p0.9999: 27.623 ms/op
                 existUser·p1.00:   28.443 ms/op

Iteration   3: 5.251 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.429 ms/op
                 existUser·p0.50:   5.030 ms/op
                 existUser·p0.90:   6.103 ms/op
                 existUser·p0.95:   6.996 ms/op
                 existUser·p0.99:   10.322 ms/op
                 existUser·p0.999:  29.105 ms/op
                 existUser·p0.9999: 33.525 ms/op
                 existUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 182050
  mean =      5.272 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 90645 
    [ 5.000,  7.500) = 82561 
    [ 7.500, 10.000) = 6981 
    [10.000, 12.500) = 1178 
    [12.500, 15.000) = 369 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 62 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.429 ms/op
     p(50.0000) =      5.005 ms/op
     p(90.0000) =      6.349 ms/op
     p(95.0000) =      7.438 ms/op
     p(99.0000) =     10.051 ms/op
     p(99.9000) =     18.905 ms/op
     p(99.9900) =     32.860 ms/op
     p(99.9990) =     35.263 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 18.269 ±(99.9%) 0.307 ms/op
# Warmup Iteration   2: 7.176 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 5.754 ±(99.9%) 0.022 ms/op
Iteration   1: 5.584 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.810 ms/op
                 getUser·p0.50:   5.243 ms/op
                 getUser·p0.90:   6.881 ms/op
                 getUser·p0.95:   7.963 ms/op
                 getUser·p0.99:   11.092 ms/op
                 getUser·p0.999:  15.364 ms/op
                 getUser·p0.9999: 27.790 ms/op
                 getUser·p1.00:   29.884 ms/op

Iteration   2: 5.059 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.958 ms/op
                 getUser·p0.50:   4.866 ms/op
                 getUser·p0.90:   5.997 ms/op
                 getUser·p0.95:   6.676 ms/op
                 getUser·p0.99:   9.028 ms/op
                 getUser·p0.999:  26.029 ms/op
                 getUser·p0.9999: 28.825 ms/op
                 getUser·p1.00:   29.032 ms/op

Iteration   3: 5.283 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.673 ms/op
                 getUser·p0.50:   5.005 ms/op
                 getUser·p0.90:   6.406 ms/op
                 getUser·p0.95:   7.324 ms/op
                 getUser·p0.99:   10.486 ms/op
                 getUser·p0.999:  27.958 ms/op
                 getUser·p0.9999: 29.917 ms/op
                 getUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 181094
  mean =      5.300 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 87608 
    [ 5.000,  7.500) = 85337 
    [ 7.500, 10.000) = 6051 
    [10.000, 12.500) = 1480 
    [12.500, 15.000) = 364 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 82 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.673 ms/op
     p(50.0000) =      5.030 ms/op
     p(90.0000) =      6.455 ms/op
     p(95.0000) =      7.340 ms/op
     p(99.0000) =     10.273 ms/op
     p(99.9000) =     25.481 ms/op
     p(99.9900) =     29.284 ms/op
     p(99.9990) =     30.022 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.953 ±(99.9%) 0.306 ms/op
# Warmup Iteration   2: 7.909 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 6.368 ±(99.9%) 0.028 ms/op
Iteration   1: 6.204 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.855 ms/op
                 listUser·p0.50:   5.841 ms/op
                 listUser·p0.90:   7.356 ms/op
                 listUser·p0.95:   9.028 ms/op
                 listUser·p0.99:   11.207 ms/op
                 listUser·p0.999:  28.935 ms/op
                 listUser·p0.9999: 34.986 ms/op
                 listUser·p1.00:   37.290 ms/op

Iteration   2: 6.493 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   0.568 ms/op
                 listUser·p0.50:   6.144 ms/op
                 listUser·p0.90:   7.840 ms/op
                 listUser·p0.95:   8.929 ms/op
                 listUser·p0.99:   11.829 ms/op
                 listUser·p0.999:  29.622 ms/op
                 listUser·p0.9999: 41.624 ms/op
                 listUser·p1.00:   43.188 ms/op

Iteration   3: 6.405 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.305 ms/op
                 listUser·p0.50:   5.972 ms/op
                 listUser·p0.90:   7.848 ms/op
                 listUser·p0.95:   9.126 ms/op
                 listUser·p0.99:   12.072 ms/op
                 listUser·p0.999:  27.102 ms/op
                 listUser·p0.9999: 28.869 ms/op
                 listUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 150719
  mean =      6.365 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 6212 
    [ 5.000, 10.000) = 140388 
    [10.000, 15.000) = 3645 
    [15.000, 20.000) = 163 
    [20.000, 25.000) = 51 
    [25.000, 30.000) = 186 
    [30.000, 35.000) = 37 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      5.972 ms/op
     p(90.0000) =      7.725 ms/op
     p(95.0000) =      9.011 ms/op
     p(99.0000) =     11.780 ms/op
     p(99.9000) =     28.279 ms/op
     p(99.9900) =     40.431 ms/op
     p(99.9990) =     42.856 ms/op
     p(99.9999) =     43.188 ms/op
    p(100.0000) =     43.188 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.799 ± 3.936  ops/ms
ClientPb.existUser                       thrpt       3   6.314 ± 3.402  ops/ms
ClientPb.getUser                         thrpt       3   5.826 ± 1.910  ops/ms
ClientPb.listUser                        thrpt       3   4.896 ± 3.311  ops/ms
ClientPb.createUser                       avgt       3   5.470 ± 2.094   ms/op
ClientPb.existUser                        avgt       3   5.197 ± 1.939   ms/op
ClientPb.getUser                          avgt       3   5.371 ± 1.766   ms/op
ClientPb.listUser                         avgt       3   6.460 ± 1.100   ms/op
ClientPb.createUser                     sample  174210   5.505 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.196           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.194           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.668           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.606           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.207           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.919           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.042           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.473           ms/op
ClientPb.existUser                      sample  182050   5.272 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.429           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.005           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.349           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.438           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.051           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.905           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.860           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.586           ms/op
ClientPb.getUser                        sample  181094   5.300 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.673           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.030           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.455           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.340           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.273           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.481           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.284           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.048           ms/op
ClientPb.listUser                       sample  150719   6.365 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.568           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.972           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.725           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.011           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.780           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.279           ms/op
ClientPb.listUser:listUser·p0.9999      sample          40.431           ms/op
ClientPb.listUser:listUser·p1.00        sample          43.188           ms/op
