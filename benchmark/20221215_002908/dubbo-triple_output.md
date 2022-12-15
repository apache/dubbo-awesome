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
# Warmup Iteration   1: 1.852 ops/ms
# Warmup Iteration   2: 4.965 ops/ms
# Warmup Iteration   3: 8.817 ops/ms
Iteration   1: 9.167 ops/ms
Iteration   2: 9.542 ops/ms
Iteration   3: 9.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.394 ±(99.9%) 3.634 ops/ms [Average]
  (min, avg, max) = (9.167, 9.394, 9.542), stdev = 0.199
  CI (99.9%): [5.760, 13.028] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.043 ops/ms
# Warmup Iteration   2: 9.154 ops/ms
# Warmup Iteration   3: 9.527 ops/ms
Iteration   1: 9.595 ops/ms
Iteration   2: 9.923 ops/ms
Iteration   3: 9.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.828 ±(99.9%) 3.703 ops/ms [Average]
  (min, avg, max) = (9.595, 9.828, 9.965), stdev = 0.203
  CI (99.9%): [6.125, 13.530] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.821 ops/ms
# Warmup Iteration   2: 8.466 ops/ms
# Warmup Iteration   3: 8.999 ops/ms
Iteration   1: 9.547 ops/ms
Iteration   2: 9.536 ops/ms
Iteration   3: 9.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.435 ±(99.9%) 3.354 ops/ms [Average]
  (min, avg, max) = (9.223, 9.435, 9.547), stdev = 0.184
  CI (99.9%): [6.081, 12.789] (assumes normal distribution)


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
# Warmup Iteration   1: 2.820 ops/ms
# Warmup Iteration   2: 7.341 ops/ms
# Warmup Iteration   3: 7.927 ops/ms
Iteration   1: 7.860 ops/ms
Iteration   2: 8.099 ops/ms
Iteration   3: 7.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.968 ±(99.9%) 2.213 ops/ms [Average]
  (min, avg, max) = (7.860, 7.968, 8.099), stdev = 0.121
  CI (99.9%): [5.755, 10.181] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.623 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.893 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.559 ±(99.9%) 0.003 ms/op
Iteration   1: 3.523 ±(99.9%) 0.005 ms/op
Iteration   2: 3.456 ±(99.9%) 0.008 ms/op
Iteration   3: 3.344 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.441 ±(99.9%) 1.649 ms/op [Average]
  (min, avg, max) = (3.344, 3.441, 3.523), stdev = 0.090
  CI (99.9%): [1.792, 5.090] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.963 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.521 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.005 ms/op
Iteration   1: 3.290 ±(99.9%) 0.003 ms/op
Iteration   2: 3.177 ±(99.9%) 0.003 ms/op
Iteration   3: 3.260 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.242 ±(99.9%) 1.066 ms/op [Average]
  (min, avg, max) = (3.177, 3.242, 3.290), stdev = 0.058
  CI (99.9%): [2.176, 4.309] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.462 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.665 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.496 ±(99.9%) 0.006 ms/op
Iteration   1: 3.417 ±(99.9%) 0.008 ms/op
Iteration   2: 3.433 ±(99.9%) 0.010 ms/op
Iteration   3: 3.409 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.419 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (3.409, 3.419, 3.433), stdev = 0.012
  CI (99.9%): [3.197, 3.642] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.004 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.361 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.064 ±(99.9%) 0.006 ms/op
Iteration   1: 4.020 ±(99.9%) 0.008 ms/op
Iteration   2: 3.936 ±(99.9%) 0.010 ms/op
Iteration   3: 3.798 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.918 ±(99.9%) 2.038 ms/op [Average]
  (min, avg, max) = (3.798, 3.918, 4.020), stdev = 0.112
  CI (99.9%): [1.880, 5.955] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.495 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.936 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.492 ±(99.9%) 0.011 ms/op
Iteration   1: 3.367 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.776 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  20.414 ms/op
                 createUser·p0.9999: 24.428 ms/op
                 createUser·p1.00:   25.035 ms/op

Iteration   2: 3.357 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.321 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  22.675 ms/op
                 createUser·p0.9999: 25.885 ms/op
                 createUser·p1.00:   26.378 ms/op

Iteration   3: 3.400 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.452 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  16.367 ms/op
                 createUser·p0.9999: 25.316 ms/op
                 createUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284291
  mean =      3.375 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12462 
    [ 2.500,  5.000) = 266546 
    [ 5.000,  7.500) = 4348 
    [ 7.500, 10.000) = 445 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     16.482 ms/op
     p(99.9900) =     25.348 ms/op
     p(99.9990) =     26.252 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.883 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.534 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.461 ±(99.9%) 0.008 ms/op
Iteration   1: 3.380 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.200 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  20.447 ms/op
                 existUser·p0.9999: 22.791 ms/op
                 existUser·p1.00:   22.938 ms/op

Iteration   2: 3.291 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   5.972 ms/op
                 existUser·p0.999:  13.204 ms/op
                 existUser·p0.9999: 26.027 ms/op
                 existUser·p1.00:   27.099 ms/op

Iteration   3: 3.265 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.610 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  13.337 ms/op
                 existUser·p0.9999: 26.703 ms/op
                 existUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289662
  mean =      3.311 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14095 
    [ 2.500,  5.000) = 271157 
    [ 5.000,  7.500) = 3603 
    [ 7.500, 10.000) = 409 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 75 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     13.337 ms/op
     p(99.9900) =     26.116 ms/op
     p(99.9990) =     27.339 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.643 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.775 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.463 ±(99.9%) 0.011 ms/op
Iteration   1: 3.524 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.272 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   3.894 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   6.177 ms/op
                 getUser·p0.999:  20.913 ms/op
                 getUser·p0.9999: 29.065 ms/op
                 getUser·p1.00:   30.048 ms/op

Iteration   2: 3.526 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.454 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.030 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   6.029 ms/op
                 getUser·p0.999:  22.052 ms/op
                 getUser·p0.9999: 24.342 ms/op
                 getUser·p1.00:   24.805 ms/op

Iteration   3: 3.539 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   5.235 ms/op
                 getUser·p0.99:   6.832 ms/op
                 getUser·p0.999:  24.456 ms/op
                 getUser·p0.9999: 28.734 ms/op
                 getUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271771
  mean =      3.530 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7973 
    [ 2.500,  5.000) = 253636 
    [ 5.000,  7.500) = 9106 
    [ 7.500, 10.000) = 731 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     21.569 ms/op
     p(99.9900) =     28.497 ms/op
     p(99.9990) =     29.795 ms/op
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
# Warmup Iteration   1: 11.491 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.377 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.160 ±(99.9%) 0.013 ms/op
Iteration   1: 4.136 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.583 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   8.028 ms/op
                 listUser·p0.999:  20.742 ms/op
                 listUser·p0.9999: 23.507 ms/op
                 listUser·p1.00:   24.871 ms/op

Iteration   2: 4.002 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  16.941 ms/op
                 listUser·p0.9999: 20.677 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   3: 4.106 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.952 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.259 ms/op
                 listUser·p0.99:   7.766 ms/op
                 listUser·p0.999:  16.007 ms/op
                 listUser·p0.9999: 17.472 ms/op
                 listUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235044
  mean =      4.081 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 224265 
    [ 5.000,  7.500) = 8011 
    [ 7.500, 10.000) = 1744 
    [10.000, 12.500) = 350 
    [12.500, 15.000) = 217 
    [15.000, 17.500) = 241 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      7.660 ms/op
     p(99.9000) =     16.351 ms/op
     p(99.9900) =     23.052 ms/op
     p(99.9990) =     23.986 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.394 ± 3.634  ops/ms
ClientPb.existUser                       thrpt       3   9.828 ± 3.703  ops/ms
ClientPb.getUser                         thrpt       3   9.435 ± 3.354  ops/ms
ClientPb.listUser                        thrpt       3   7.968 ± 2.213  ops/ms
ClientPb.createUser                       avgt       3   3.441 ± 1.649   ms/op
ClientPb.existUser                        avgt       3   3.242 ± 1.066   ms/op
ClientPb.getUser                          avgt       3   3.419 ± 0.223   ms/op
ClientPb.listUser                         avgt       3   3.918 ± 2.038   ms/op
ClientPb.createUser                     sample  284291   3.375 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.321           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.310           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.055           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.661           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.482           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.348           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.378           ms/op
ClientPb.existUser                      sample  289662   3.311 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.879           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.248           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.949           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.337           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.116           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.180           ms/op
ClientPb.getUser                        sample  271771   3.530 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.871           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.400           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.010           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.579           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.414           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.569           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.497           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.048           ms/op
ClientPb.listUser                       sample  235044   4.081 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.952           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.940           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.660           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.351           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.052           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.871           ms/op
