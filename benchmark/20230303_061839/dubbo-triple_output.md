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
# Warmup Iteration   1: 1.895 ops/ms
# Warmup Iteration   2: 5.183 ops/ms
# Warmup Iteration   3: 8.868 ops/ms
Iteration   1: 9.404 ops/ms
Iteration   2: 9.306 ops/ms
Iteration   3: 9.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.403 ±(99.9%) 1.748 ops/ms [Average]
  (min, avg, max) = (9.306, 9.403, 9.498), stdev = 0.096
  CI (99.9%): [7.655, 11.151] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.255 ops/ms
# Warmup Iteration   2: 8.690 ops/ms
# Warmup Iteration   3: 9.520 ops/ms
Iteration   1: 9.452 ops/ms
Iteration   2: 9.770 ops/ms
Iteration   3: 9.605 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.609 ±(99.9%) 2.896 ops/ms [Average]
  (min, avg, max) = (9.452, 9.609, 9.770), stdev = 0.159
  CI (99.9%): [6.713, 12.505] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.447 ops/ms
# Warmup Iteration   2: 9.025 ops/ms
# Warmup Iteration   3: 9.424 ops/ms
Iteration   1: 9.346 ops/ms
Iteration   2: 9.718 ops/ms
Iteration   3: 9.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.463 ±(99.9%) 4.044 ops/ms [Average]
  (min, avg, max) = (9.324, 9.463, 9.718), stdev = 0.222
  CI (99.9%): [5.419, 13.507] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.836 ops/ms
# Warmup Iteration   2: 7.311 ops/ms
# Warmup Iteration   3: 7.992 ops/ms
Iteration   1: 8.008 ops/ms
Iteration   2: 8.279 ops/ms
Iteration   3: 7.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.041 ±(99.9%) 4.080 ops/ms [Average]
  (min, avg, max) = (7.836, 8.041, 8.279), stdev = 0.224
  CI (99.9%): [3.960, 12.121] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 10.472 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 3.758 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.010 ms/op
Iteration   1: 3.415 ±(99.9%) 0.006 ms/op
Iteration   2: 3.405 ±(99.9%) 0.007 ms/op
Iteration   3: 3.406 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.409 ±(99.9%) 0.105 ms/op [Average]
  (min, avg, max) = (3.405, 3.409, 3.415), stdev = 0.006
  CI (99.9%): [3.304, 3.514] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.175 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.512 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.392 ±(99.9%) 0.007 ms/op
Iteration   1: 3.256 ±(99.9%) 0.004 ms/op
Iteration   2: 3.268 ±(99.9%) 0.004 ms/op
Iteration   3: 3.368 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.297 ±(99.9%) 1.125 ms/op [Average]
  (min, avg, max) = (3.256, 3.297, 3.368), stdev = 0.062
  CI (99.9%): [2.172, 4.422] (assumes normal distribution)


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
# Warmup Iteration   1: 9.207 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.733 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.003 ms/op
Iteration   1: 3.462 ±(99.9%) 0.007 ms/op
Iteration   2: 3.276 ±(99.9%) 0.011 ms/op
Iteration   3: 3.328 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.355 ±(99.9%) 1.757 ms/op [Average]
  (min, avg, max) = (3.276, 3.355, 3.462), stdev = 0.096
  CI (99.9%): [1.599, 5.112] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.910 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.595 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.068 ±(99.9%) 0.007 ms/op
Iteration   1: 3.965 ±(99.9%) 0.010 ms/op
Iteration   2: 3.852 ±(99.9%) 0.013 ms/op
Iteration   3: 4.008 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.941 ±(99.9%) 1.473 ms/op [Average]
  (min, avg, max) = (3.852, 3.941, 4.008), stdev = 0.081
  CI (99.9%): [2.469, 5.414] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.151 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.926 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.519 ±(99.9%) 0.011 ms/op
Iteration   1: 3.412 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.282 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  21.186 ms/op
                 createUser·p0.9999: 24.006 ms/op
                 createUser·p1.00:   24.936 ms/op

Iteration   2: 3.479 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.382 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  21.660 ms/op
                 createUser·p0.9999: 24.832 ms/op
                 createUser·p1.00:   26.313 ms/op

Iteration   3: 3.430 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.239 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  20.143 ms/op
                 createUser·p0.9999: 28.705 ms/op
                 createUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278933
  mean =      3.440 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14260 
    [ 2.500,  5.000) = 258675 
    [ 5.000,  7.500) = 5105 
    [ 7.500, 10.000) = 455 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 129 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      1.239 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     20.644 ms/op
     p(99.9900) =     26.873 ms/op
     p(99.9990) =     29.065 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.831 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.602 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.368 ±(99.9%) 0.009 ms/op
Iteration   1: 3.284 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.565 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   5.675 ms/op
                 existUser·p0.999:  14.157 ms/op
                 existUser·p0.9999: 23.626 ms/op
                 existUser·p1.00:   24.248 ms/op

Iteration   2: 3.251 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.294 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  12.288 ms/op
                 existUser·p0.9999: 27.350 ms/op
                 existUser·p1.00:   29.131 ms/op

Iteration   3: 3.367 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.163 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.826 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   5.359 ms/op
                 existUser·p0.999:  21.267 ms/op
                 existUser·p0.9999: 26.313 ms/op
                 existUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290874
  mean =      3.300 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11942 
    [ 2.500,  5.000) = 273425 
    [ 5.000,  7.500) = 4718 
    [ 7.500, 10.000) = 437 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 75 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     13.912 ms/op
     p(99.9900) =     26.572 ms/op
     p(99.9990) =     29.071 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


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
# Warmup Iteration   1: 9.676 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.481 ±(99.9%) 0.011 ms/op
Iteration   1: 3.449 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.329 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.353 ms/op
                 getUser·p0.99:   6.521 ms/op
                 getUser·p0.999:  14.381 ms/op
                 getUser·p0.9999: 23.318 ms/op
                 getUser·p1.00:   24.314 ms/op

Iteration   2: 3.407 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.784 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   5.849 ms/op
                 getUser·p0.999:  21.987 ms/op
                 getUser·p0.9999: 24.879 ms/op
                 getUser·p1.00:   25.592 ms/op

Iteration   3: 3.543 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.532 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.182 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  19.399 ms/op
                 getUser·p0.9999: 28.158 ms/op
                 getUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276927
  mean =      3.466 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6431 
    [ 2.500,  5.000) = 261130 
    [ 5.000,  7.500) = 8208 
    [ 7.500, 10.000) = 658 
    [10.000, 12.500) = 197 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =     17.859 ms/op
     p(99.9900) =     26.749 ms/op
     p(99.9990) =     29.673 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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
# Warmup Iteration   1: 10.765 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.417 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.089 ±(99.9%) 0.014 ms/op
Iteration   1: 4.009 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  16.813 ms/op
                 listUser·p0.9999: 24.544 ms/op
                 listUser·p1.00:   24.936 ms/op

Iteration   2: 4.005 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.958 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  16.204 ms/op
                 listUser·p0.9999: 24.379 ms/op
                 listUser·p1.00:   24.412 ms/op

Iteration   3: 3.863 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.898 ms/op
                 listUser·p0.999:  15.126 ms/op
                 listUser·p0.9999: 17.072 ms/op
                 listUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242453
  mean =      3.958 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 235367 
    [ 5.000,  7.500) = 5017 
    [ 7.500, 10.000) = 1133 
    [10.000, 12.500) = 384 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 253 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.958 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     16.138 ms/op
     p(99.9900) =     24.339 ms/op
     p(99.9990) =     24.829 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.403 ± 1.748  ops/ms
ClientPb.existUser                       thrpt       3   9.609 ± 2.896  ops/ms
ClientPb.getUser                         thrpt       3   9.463 ± 4.044  ops/ms
ClientPb.listUser                        thrpt       3   8.041 ± 4.080  ops/ms
ClientPb.createUser                       avgt       3   3.409 ± 0.105   ms/op
ClientPb.existUser                        avgt       3   3.297 ± 1.125   ms/op
ClientPb.getUser                          avgt       3   3.355 ± 1.757   ms/op
ClientPb.listUser                         avgt       3   3.941 ± 1.473   ms/op
ClientPb.createUser                     sample  278933   3.440 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.239           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.186           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.743           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.644           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.873           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.131           ms/op
ClientPb.existUser                      sample  290874   3.300 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.163           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.985           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.521           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.912           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.572           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.131           ms/op
ClientPb.getUser                        sample  276927   3.466 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.329           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.355           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.415           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.234           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.859           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.749           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.278           ms/op
ClientPb.listUser                       sample  242453   3.958 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.958           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.242           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.138           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.339           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.936           ms/op
